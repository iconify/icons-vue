<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k57p5qbxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k57p5qbxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:playerfm" /></template>
