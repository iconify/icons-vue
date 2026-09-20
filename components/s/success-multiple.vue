<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg-h_4-0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="eg-h_4-0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:success-multiple" /></template>
