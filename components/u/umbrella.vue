<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsnh_gbkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="fsnh_gbkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:umbrella" /></template>
