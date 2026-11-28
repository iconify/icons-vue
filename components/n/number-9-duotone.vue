<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbkck_nrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbkck_nrq primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:number-9-duotone" /></template>
