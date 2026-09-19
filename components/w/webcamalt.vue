<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc4cqtmyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":833,"height":1024};
const content = `<path class="lc4cqtmyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:webcamalt" /></template>
