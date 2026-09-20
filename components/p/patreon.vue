<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwwhpnb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwwhpnb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:patreon" /></template>
