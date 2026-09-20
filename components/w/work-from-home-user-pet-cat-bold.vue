<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr4lprbfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qr4lprbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:work-from-home-user-pet-cat-bold" /></template>
