<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wte7h9b6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wte7h9b6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-paper-plane" /></template>
