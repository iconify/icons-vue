<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pep0p17_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pep0p17_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:text-align-justify-start" /></template>
