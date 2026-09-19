<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv-j_tzgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pv-j_tzgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:soon-arrow" /></template>
