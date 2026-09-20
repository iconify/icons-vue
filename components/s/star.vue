<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k12o0ub5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k12o0ub5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:star" /></template>
