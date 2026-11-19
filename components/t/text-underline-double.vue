<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz_1w_b4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lz_1w_b4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:text-underline-double" /></template>
