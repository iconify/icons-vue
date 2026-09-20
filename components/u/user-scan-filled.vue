<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip6m2qbtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ip6m2qbtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-scan-filled" /></template>
