<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/roqxmxb4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="roqxmxb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:repeat" /></template>
