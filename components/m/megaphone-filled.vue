<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npdvl2brz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npdvl2brz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:megaphone-filled" /></template>
