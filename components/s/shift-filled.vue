<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_-4vlmxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="w_-4vlmxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:shift-filled" /></template>
