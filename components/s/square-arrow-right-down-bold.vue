<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz9r1ynfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lz9r1ynfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-arrow-right-down-bold" /></template>
