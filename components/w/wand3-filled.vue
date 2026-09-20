<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4v_j9b_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4v_j9b_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:wand3-filled" /></template>
