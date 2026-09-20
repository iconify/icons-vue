<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xco58ibdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="xco58ibdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:next" /></template>
