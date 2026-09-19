<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in_3xv-0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="in_3xv-0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-stack-3d-down-right-fill" /></template>
