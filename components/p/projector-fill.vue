<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no9xs_bel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="no9xs_bel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:projector-fill" /></template>
