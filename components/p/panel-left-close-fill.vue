<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uarib6_cc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uarib6_cc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-left-close-fill" /></template>
