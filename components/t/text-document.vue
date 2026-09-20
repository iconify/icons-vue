<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7lllzzkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="k7lllzzkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:text-document" /></template>
