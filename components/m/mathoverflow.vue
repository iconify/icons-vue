<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqtblfb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xqtblfb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:mathoverflow" /></template>
