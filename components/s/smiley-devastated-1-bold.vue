<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_eln7hov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_eln7hov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:smiley-devastated-1-bold" /></template>
