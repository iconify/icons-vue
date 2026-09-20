<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng3tch7ly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ng3tch7ly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:otter-solid" /></template>
