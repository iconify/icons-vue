<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpd_00bvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tpd_00bvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-arrow-left-down-outline" /></template>
