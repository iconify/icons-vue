<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_i_gwb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_i_gwb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:seal-filled" /></template>
