<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iiaxrbbmg.css';
import '../../css/f/fit1ekbah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iiaxrbbmg"/><path class="fit1ekbah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:xem" /></template>
