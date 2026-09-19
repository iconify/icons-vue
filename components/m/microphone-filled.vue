<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-sti_bko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="p-sti_bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:microphone-filled" /></template>
