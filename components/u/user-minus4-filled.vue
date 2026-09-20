<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee-bfbb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ee-bfbb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-minus4-filled" /></template>
