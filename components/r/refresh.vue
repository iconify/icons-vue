<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db7cgxb3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-1.5,"top":-2.5};
const content = `<path class="db7cgxb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:refresh" /></template>
