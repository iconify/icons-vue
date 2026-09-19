<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oaky5lbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oaky5lbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:salah" /></template>
