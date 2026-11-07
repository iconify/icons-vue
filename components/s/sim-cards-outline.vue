<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5yhef5il.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m5yhef5il"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sim-cards-outline" /></template>
