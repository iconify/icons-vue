<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ori6x2u_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ori6x2u_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:pentagon" /></template>
