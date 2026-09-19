<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jddxo1boq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jddxo1boq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:rocket-solid" /></template>
