<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr_oojzww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zr_oojzww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:mail" /></template>
