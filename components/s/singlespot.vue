<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it9q_rbmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="it9q_rbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:singlespot" /></template>
