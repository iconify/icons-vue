<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow83bgbqz.css';
import '../../css/p/p0c2m7eex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ow83bgbqz"/><path class="p0c2m7eex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-information-circle-outline" /></template>
