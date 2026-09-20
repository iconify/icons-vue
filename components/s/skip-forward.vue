<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0aslnhvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0aslnhvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:skip-forward" /></template>
