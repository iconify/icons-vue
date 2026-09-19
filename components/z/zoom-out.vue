<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2_k3ejup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="h2_k3ejup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:zoom-out" /></template>
