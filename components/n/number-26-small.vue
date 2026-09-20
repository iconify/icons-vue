<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llgj6_bel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="llgj6_bel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-26-small" /></template>
