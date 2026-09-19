<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uf7a0hbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="uf7a0hbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:mail-solid" /></template>
