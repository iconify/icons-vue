<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwqwepbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwqwepbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:network-off-fill" /></template>
