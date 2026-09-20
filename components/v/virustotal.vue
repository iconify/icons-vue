<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukqv-xs0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukqv-xs0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:virustotal" /></template>
