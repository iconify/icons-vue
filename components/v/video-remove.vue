<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mee_wqb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mee_wqb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:video-remove" /></template>
