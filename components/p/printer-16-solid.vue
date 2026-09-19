<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0bsh78wk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="q0bsh78wk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:printer-16-solid" /></template>
