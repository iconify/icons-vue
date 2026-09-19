<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs3jv3vjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="qs3jv3vjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:turn-sign-bold" /></template>
