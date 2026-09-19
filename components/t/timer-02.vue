<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp2ocqb2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cp2ocqb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:timer-02" /></template>
