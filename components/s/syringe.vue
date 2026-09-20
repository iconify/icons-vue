<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hksa8qn3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hksa8qn3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:syringe" /></template>
