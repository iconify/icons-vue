<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tikxy6xmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tikxy6xmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:minio" /></template>
