<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4b02zbhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="t4b02zbhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:quote-bubble" /></template>
