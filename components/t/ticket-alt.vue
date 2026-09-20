<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tysv080gv.css';
import '../../css/r/rbu861b0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="tysv080gv"/><path class="rbu861b0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:ticket-alt" /></template>
