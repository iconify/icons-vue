<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba6a98byv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ba6a98byv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-stack-3d-up" /></template>
