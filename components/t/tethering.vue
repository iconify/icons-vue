<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djtt_e1bf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="djtt_e1bf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:tethering" /></template>
