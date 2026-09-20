<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kln6l2-vx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="kln6l2-vx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:message-outline" /></template>
