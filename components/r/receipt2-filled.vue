<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw-ztc7eo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bw-ztc7eo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:receipt2-filled" /></template>
