<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx3ehvb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wx3ehvb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:phone-cross" /></template>
