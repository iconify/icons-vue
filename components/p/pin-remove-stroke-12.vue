<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_hoj2etx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="m_hoj2etx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:pin-remove-stroke-12" /></template>
