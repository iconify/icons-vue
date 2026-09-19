<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv2yl7bqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kv2yl7bqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-equal-bold" /></template>
