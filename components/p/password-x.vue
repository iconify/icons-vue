<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5fj_c4mr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5fj_c4mr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:password-x" /></template>
