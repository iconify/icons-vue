<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc67xp7dw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":400,"height":90};
const content = `<path class="kc67xp7dw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:santander" /></template>
