<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd3iv7bau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nd3iv7bau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:tent" /></template>
