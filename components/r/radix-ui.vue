<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trv0p2amd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trv0p2amd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:radix-ui" /></template>
