<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tblh_accd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tblh_accd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:text-circle-rectangle-filled" /></template>
