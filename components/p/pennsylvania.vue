<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhxvufbpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vhxvufbpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pennsylvania" /></template>
