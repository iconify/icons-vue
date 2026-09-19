<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip22f7bew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ip22f7bew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:text-align-center" /></template>
