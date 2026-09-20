<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vee1z3biw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vee1z3biw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:zoom-in" /></template>
