<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg10809pc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cg10809pc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:receipt-clock" /></template>
