<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr6ahtbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mr6ahtbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:moon-phase-3" /></template>
