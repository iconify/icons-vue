<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntnxv4bnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ntnxv4bnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:ticket-sale-filled" /></template>
