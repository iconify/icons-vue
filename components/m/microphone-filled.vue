<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msx1qubsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msx1qubsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:microphone-filled" /></template>
