<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmf7pn_8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmf7pn_8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:numbers-5" /></template>
