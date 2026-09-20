<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kip8j-bqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kip8j-bqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:receipt-pound-filled" /></template>
