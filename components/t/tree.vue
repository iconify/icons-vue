<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-h_l0kyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-h_l0kyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:tree" /></template>
