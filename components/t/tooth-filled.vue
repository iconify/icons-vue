<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvg0ib-hb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvg0ib-hb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tooth-filled" /></template>
