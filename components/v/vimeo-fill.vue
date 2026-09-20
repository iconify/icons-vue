<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd-50n3ja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bd-50n3ja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:vimeo-fill" /></template>
