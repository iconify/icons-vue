<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa_gikbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aa_gikbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:shape-cube-bold" /></template>
