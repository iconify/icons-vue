<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxbiho01o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uxbiho01o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:stream-solid" /></template>
