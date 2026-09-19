<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-tqbb_cj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-tqbb_cj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:moon" /></template>
