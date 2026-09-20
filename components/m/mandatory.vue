<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eob2i8v4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eob2i8v4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:mandatory" /></template>
