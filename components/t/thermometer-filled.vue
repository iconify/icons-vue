<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwpu5t_vw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwpu5t_vw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:thermometer-filled" /></template>
