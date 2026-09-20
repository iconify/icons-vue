<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7gxj6bpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s7gxj6bpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:two-above-water" /></template>
