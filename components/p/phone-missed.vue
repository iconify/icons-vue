<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2hs_cbbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2hs_cbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:phone-missed" /></template>
