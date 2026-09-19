<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecobcdb3u.css';
import '../../css/t/tgdfm4b2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ecobcdb3u"/><path class="tgdfm4b2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:user-check" /></template>
