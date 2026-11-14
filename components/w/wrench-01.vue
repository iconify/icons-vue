<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3c8y6bel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3c8y6bel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:wrench-01" /></template>
