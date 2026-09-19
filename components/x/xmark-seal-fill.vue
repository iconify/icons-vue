<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmb40b8ah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="nmb40b8ah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:xmark-seal-fill" /></template>
