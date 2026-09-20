<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxmp01xwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="yxmp01xwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:travel-hotel-towel-towel-spa-wet-water-hot" /></template>
