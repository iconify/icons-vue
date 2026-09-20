<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6wqijbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="z6wqijbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:rules-filled" /></template>
