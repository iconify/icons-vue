<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9wtobbqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="w9wtobbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:voice" /></template>
