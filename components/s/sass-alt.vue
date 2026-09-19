<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku0u7w7xy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ku0u7w7xy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:sass-alt" /></template>
