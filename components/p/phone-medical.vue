<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfcb0sdvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mfcb0sdvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:phone-medical" /></template>
