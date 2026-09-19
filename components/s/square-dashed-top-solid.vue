<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2nrntb2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2nrntb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:square-dashed-top-solid" /></template>
