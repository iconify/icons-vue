<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgc0kgdcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgc0kgdcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pin-filled" /></template>
