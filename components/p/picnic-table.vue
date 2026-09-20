<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb-2c0eis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gb-2c0eis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:picnic-table" /></template>
