<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_vn3o3pm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_vn3o3pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:play-24" /></template>
