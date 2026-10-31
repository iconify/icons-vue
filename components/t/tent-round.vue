<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1odkg-wd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1odkg-wd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tent-round" /></template>
