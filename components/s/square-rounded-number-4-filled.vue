<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqtlszbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqtlszbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-number-4-filled" /></template>
