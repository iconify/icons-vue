<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwidnkbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwidnkbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:spin" /></template>
