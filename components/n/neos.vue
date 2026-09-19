<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsq-55bis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dsq-55bis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:neos" /></template>
