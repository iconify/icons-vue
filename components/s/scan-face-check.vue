<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy35zvxwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zy35zvxwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:scan-face-check" /></template>
