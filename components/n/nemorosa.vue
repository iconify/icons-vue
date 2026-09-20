<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chs0ajpjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="chs0ajpjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nemorosa" /></template>
