<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb0uxtbto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="wb0uxtbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:sidebar" /></template>
