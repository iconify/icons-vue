<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua36r_beu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ua36r_beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:receipt-rupee-filled" /></template>
