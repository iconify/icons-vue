<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgk_s4scd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgk_s4scd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:youtube" /></template>
