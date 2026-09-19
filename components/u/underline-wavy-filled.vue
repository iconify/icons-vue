<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp0xn1j2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rp0xn1j2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:underline-wavy-filled" /></template>
