<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8a7etb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8a7etb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:stethoscope-filled" /></template>
