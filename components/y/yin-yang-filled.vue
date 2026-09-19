<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw-cofgvd.css';
import '../../css/t/tngwchp1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fw-cofgvd"/><path class="tngwchp1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:yin-yang-filled" /></template>
