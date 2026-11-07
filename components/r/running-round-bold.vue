<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp8lrpbea.css';
import '../../css/i/isx_b_b0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cp8lrpbea"/><path clip-rule="evenodd" class="isx_b_b0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:running-round-bold" /></template>
