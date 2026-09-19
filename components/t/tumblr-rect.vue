<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byz7bnbzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="byz7bnbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:tumblr-rect" /></template>
