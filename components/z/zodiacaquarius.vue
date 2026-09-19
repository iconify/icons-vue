<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yev3sduco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":896};
const content = `<path class="yev3sduco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:zodiacaquarius" /></template>
