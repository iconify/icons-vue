<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-fhkt0hx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f-fhkt0hx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:turntable-minimalistic-bold" /></template>
