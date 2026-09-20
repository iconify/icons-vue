<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tipk8qtgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tipk8qtgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:microscope" /></template>
