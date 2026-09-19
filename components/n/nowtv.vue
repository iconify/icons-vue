<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew_qcvbbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ew_qcvbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:nowtv" /></template>
