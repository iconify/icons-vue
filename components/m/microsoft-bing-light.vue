<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t43humgww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t43humgww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-bing-light" /></template>
