<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqs4gbbjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":432};
const content = `<path class="oqs4gbbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:rotate-right" /></template>
