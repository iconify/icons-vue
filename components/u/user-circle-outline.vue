<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo-q0jb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo-q0jb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:user-circle-outline" /></template>
