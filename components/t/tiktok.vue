<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ani_nmk9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ani_nmk9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:tiktok" /></template>
