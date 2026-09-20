<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojovl0byn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojovl0byn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:trading-pattern-up" /></template>
