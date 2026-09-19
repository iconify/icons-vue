<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1qy5wj_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="i1qy5wj_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:qrcode" /></template>
