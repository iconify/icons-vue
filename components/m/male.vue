<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpp5awb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kpp5awb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:male" /></template>
