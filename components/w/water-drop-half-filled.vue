<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk99llbma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fk99llbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:water-drop-half-filled" /></template>
