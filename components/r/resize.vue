<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca5_jfd3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":528,"height":520};
const content = `<path class="ca5_jfd3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:resize" /></template>
