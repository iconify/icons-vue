<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q__q39r5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q__q39r5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:syringe" /></template>
