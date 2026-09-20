<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6si3pb8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6si3pb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:swipe-up-filled" /></template>
