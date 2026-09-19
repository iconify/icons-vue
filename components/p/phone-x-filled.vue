<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddpxy9bza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddpxy9bza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:phone-x-filled" /></template>
