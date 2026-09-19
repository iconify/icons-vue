<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1j2-hbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1j2-hbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:thumbs-down-outline" /></template>
