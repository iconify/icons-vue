<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow83bgbqz.css';
import '../../css/x/xti0nob1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ow83bgbqz"/><path class="xti0nob1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-remove-circle-outline" /></template>
