<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0x476ygt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="a0x476ygt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:right" /></template>
