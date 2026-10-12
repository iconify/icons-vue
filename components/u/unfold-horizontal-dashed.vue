<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbu1mdbbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbu1mdbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:unfold-horizontal-dashed" /></template>
