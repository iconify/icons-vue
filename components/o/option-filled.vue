<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us2_t99qk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="us2_t99qk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:option-filled" /></template>
