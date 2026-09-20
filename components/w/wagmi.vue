<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtl--8bqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtl--8bqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:wagmi" /></template>
