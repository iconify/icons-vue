<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/poq_cbc-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="poq_cbc-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:weight-24px" /></template>
