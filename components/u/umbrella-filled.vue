<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhm33acgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhm33acgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:umbrella-filled" /></template>
