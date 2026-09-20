<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msa3vwofs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msa3vwofs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:toggltrack" /></template>
