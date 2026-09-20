<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6jbv-bsq.css';
import '../../css/t/tvn_kseps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6jbv-bsq"/><path class="tvn_kseps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:single-woman-home-bold" /></template>
