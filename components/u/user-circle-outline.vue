<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv40kvbll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yv40kvbll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:user-circle-outline" /></template>
