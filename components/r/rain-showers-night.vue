<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v63drczcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="v63drczcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:rain-showers-night" /></template>
