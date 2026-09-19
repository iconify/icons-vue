<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku1p59bor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ku1p59bor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:text-indent-less" /></template>
