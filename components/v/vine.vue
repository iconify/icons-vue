<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sym4uikbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sym4uikbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:vine" /></template>
