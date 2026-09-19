<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljaub6bdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljaub6bdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:radio-off" /></template>
