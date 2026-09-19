<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t433r3pkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t433r3pkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:mention" /></template>
