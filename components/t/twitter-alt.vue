<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwsr9cbux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":448};
const content = `<path class="uwsr9cbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:twitter-alt" /></template>
