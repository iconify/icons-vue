<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-1zhdc2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-1zhdc2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:risc-v" /></template>
