<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqxm_jb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="rqxm_jb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:shopping-bag" /></template>
