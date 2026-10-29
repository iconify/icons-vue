<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh-_uconv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gh-_uconv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:zap-solid" /></template>
