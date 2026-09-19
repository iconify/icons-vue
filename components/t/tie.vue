<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4_lk-lvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4_lk-lvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tie" /></template>
