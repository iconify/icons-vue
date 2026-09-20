<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib276704k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ib276704k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:phone-solid" /></template>
