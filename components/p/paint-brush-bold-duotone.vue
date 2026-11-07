<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft-3lt0tv.css';
import '../../css/n/neh-dob8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft-3lt0tv"/><path class="neh-dob8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paint-brush-bold-duotone" /></template>
