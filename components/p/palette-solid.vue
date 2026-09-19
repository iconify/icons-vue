<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu22fmb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qu22fmb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:palette-solid" /></template>
