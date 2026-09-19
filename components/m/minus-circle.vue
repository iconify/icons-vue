<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iks3biblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iks3biblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:minus-circle" /></template>
