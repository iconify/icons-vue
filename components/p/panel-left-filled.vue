<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hchuaz8ae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hchuaz8ae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:panel-left-filled" /></template>
