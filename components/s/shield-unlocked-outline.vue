<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sio0q-bpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sio0q-bpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shield-unlocked-outline" /></template>
