<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu1961ykc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zu1961ykc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:social-vimeo-circular" /></template>
