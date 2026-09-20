<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6if_2bkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h6if_2bkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:scooter" /></template>
