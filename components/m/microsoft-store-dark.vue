<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkix5db5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wkix5db5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-store-dark" /></template>
