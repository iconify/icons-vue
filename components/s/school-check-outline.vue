<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1fdmvbja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1fdmvbja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:school-check-outline" /></template>
