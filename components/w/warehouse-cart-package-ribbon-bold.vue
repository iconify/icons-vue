<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aio2xib1e.css';
import '../../css/h/hp8gss3tw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aio2xib1e"/><path class="hp8gss3tw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:warehouse-cart-package-ribbon-bold" /></template>
