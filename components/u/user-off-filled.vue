<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc_r4ms4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mc_r4ms4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-off-filled" /></template>
