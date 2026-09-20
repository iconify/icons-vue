<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncz3mjb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncz3mjb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:vexxhost" /></template>
