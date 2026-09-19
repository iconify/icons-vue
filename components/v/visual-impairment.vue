<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpo8tnbfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpo8tnbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:visual-impairment" /></template>
