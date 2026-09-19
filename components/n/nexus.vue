<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aanrx1ttf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="aanrx1ttf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:nexus" /></template>
