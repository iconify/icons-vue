<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7jt5ebyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="o7jt5ebyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:phone-down-above-211" /></template>
