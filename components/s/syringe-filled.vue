<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4mad_nxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k4mad_nxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:syringe-filled" /></template>
