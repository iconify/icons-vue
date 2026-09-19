<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwpj8qbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwpj8qbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:mobile-ring-filled" /></template>
