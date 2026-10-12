<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngyrl8b-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ngyrl8b-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:pipette-filled" /></template>
