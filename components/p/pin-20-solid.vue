<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsq404tth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nsq404tth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:pin-20-solid" /></template>
