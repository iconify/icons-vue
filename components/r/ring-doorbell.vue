<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lds2ulbvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lds2ulbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ring-doorbell" /></template>
