<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn74gbcir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="tn74gbcir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:retweet" /></template>
