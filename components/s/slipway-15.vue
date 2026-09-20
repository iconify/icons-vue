<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aksfx28xz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="aksfx28xz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:slipway-15" /></template>
