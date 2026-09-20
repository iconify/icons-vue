<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsy0312ov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wsy0312ov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tipi-campsite-with-yen-yuan" /></template>
