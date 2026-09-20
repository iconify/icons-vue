<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc2rqimtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wc2rqimtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sugarcane-stalks-with-top-leaves" /></template>
