<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6tq3ljje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6tq3ljje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:takeaway-filled" /></template>
