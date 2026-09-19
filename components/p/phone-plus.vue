<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klsefs8bw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klsefs8bw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:phone-plus" /></template>
