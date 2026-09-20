<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eapga2xru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eapga2xru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:scissors-line" /></template>
