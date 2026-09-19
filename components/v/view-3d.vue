<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwltb-50z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="pwltb-50z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:view-3d" /></template>
