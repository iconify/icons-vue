<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrc0clbfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="nrc0clbfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:rectangle-fill-on-rectangle-angled-fill" /></template>
