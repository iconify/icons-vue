<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epyglrb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="epyglrb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:remote-access" /></template>
