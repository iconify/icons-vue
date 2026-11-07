<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eeidxnbcj.css';
import '../../css/l/loxl4zb4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eeidxnbcj"/><path class="loxl4zb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ranking-bold" /></template>
