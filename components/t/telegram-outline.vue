<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ep2_iimky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ep2_iimky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:telegram-outline" /></template>
