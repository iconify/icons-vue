<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3_tk1btp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3_tk1btp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-transfer-diagonal-bold" /></template>
