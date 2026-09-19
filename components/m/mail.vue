<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqhvr3bzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1360,"height":1000};
const content = `<path class="hqhvr3bzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:mail" /></template>
