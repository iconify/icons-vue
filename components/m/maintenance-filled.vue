<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq_gujbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lq_gujbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:maintenance-filled" /></template>
