<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qescwxe_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="qescwxe_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:stopwatch-filled" /></template>
