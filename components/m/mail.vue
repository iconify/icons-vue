<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj6h2wbzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":614};
const content = `<path class="gj6h2wbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:mail" /></template>
