<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvi86xbpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rvi86xbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:unlock-outline" /></template>
