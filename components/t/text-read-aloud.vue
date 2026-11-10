<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-f5n_baw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-f5n_baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:text-read-aloud" /></template>
