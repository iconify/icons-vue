<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qopg05uxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":448};
const content = `<path class="qopg05uxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:retweet" /></template>
