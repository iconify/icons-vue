<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emi064kuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emi064kuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:receive-outline" /></template>
