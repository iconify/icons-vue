<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkkg48bsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkkg48bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:phone-flash-light" /></template>
