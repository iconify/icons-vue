<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4tu1bc1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="o4tu1bc1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:p-wide-with-arrow-right" /></template>
