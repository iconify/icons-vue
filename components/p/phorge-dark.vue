<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vscx7yblo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vscx7yblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:phorge-dark" /></template>
