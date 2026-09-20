<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9vru-sib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="h9vru-sib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:signal-loading" /></template>
