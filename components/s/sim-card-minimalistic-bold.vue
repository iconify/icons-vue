<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha-2i6-rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ha-2i6-rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sim-card-minimalistic-bold" /></template>
