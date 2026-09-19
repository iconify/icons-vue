<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpgbx2bsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpgbx2bsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:shade-rchiileea-v1" /></template>
