<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcohcvn_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcohcvn_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:web-section" /></template>
