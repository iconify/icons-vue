<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhg0jyb_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhg0jyb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:moon-phase-1" /></template>
