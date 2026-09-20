<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg7s-f8zw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dg7s-f8zw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:stack-3" /></template>
