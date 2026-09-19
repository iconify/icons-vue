<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txy7xkb8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="txy7xkb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:rectangle-fill-badge-xmark" /></template>
