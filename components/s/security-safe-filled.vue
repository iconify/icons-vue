<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsx1q7bdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsx1q7bdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:security-safe-filled" /></template>
