<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2x85_bqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":464};
const content = `<path class="v2x85_bqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:msn-messenger" /></template>
