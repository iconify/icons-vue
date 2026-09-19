<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6zf4mfqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="u6zf4mfqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:python" /></template>
