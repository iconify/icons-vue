<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqdio7zmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqdio7zmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:t-shirt-broken" /></template>
