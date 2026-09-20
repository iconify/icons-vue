<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5jp2kbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5jp2kbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:setting3-filled" /></template>
