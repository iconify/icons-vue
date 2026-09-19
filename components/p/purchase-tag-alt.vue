<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-c1osbtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-c1osbtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:purchase-tag-alt" /></template>
