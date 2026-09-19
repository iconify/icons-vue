<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0lbcs7zx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="l0lbcs7zx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:raised-back-of-hand-small" /></template>
