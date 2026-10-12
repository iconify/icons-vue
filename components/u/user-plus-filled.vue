<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk2pvgbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk2pvgbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-plus-filled" /></template>
