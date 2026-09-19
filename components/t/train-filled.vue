<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6__l5bzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6__l5bzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:train-filled" /></template>
