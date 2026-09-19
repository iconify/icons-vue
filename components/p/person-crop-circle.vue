<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4w4s00tn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="i4w4s00tn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:person-crop-circle" /></template>
