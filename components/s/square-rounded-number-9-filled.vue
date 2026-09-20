<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe_qc0b-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe_qc0b-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-number-9-filled" /></template>
