<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt7sn_o_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt7sn_o_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:signal" /></template>
