<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqeyqsb0i.css';
import '../../css/n/nn7oqiafx.css';
import '../../css/v/vfk2nmbnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqeyqsb0i"/><path class="nn7oqiafx"/><path clip-rule="evenodd" class="vfk2nmbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:passport-minimalistic-bold" /></template>
