<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocjhggbvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ocjhggbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:prescription-solid" /></template>
