<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmr2z5nok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="cmr2z5nok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:suit-spade" /></template>
