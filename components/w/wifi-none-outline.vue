<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjoyhab7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qjoyhab7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:wifi-none-outline" /></template>
