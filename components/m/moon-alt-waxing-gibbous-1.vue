<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn4bs8axk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="bn4bs8axk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-alt-waxing-gibbous-1" /></template>
