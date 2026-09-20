<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt6k4ej1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-1.5};
const content = `<path class="zt6k4ej1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:smiley-f" /></template>
