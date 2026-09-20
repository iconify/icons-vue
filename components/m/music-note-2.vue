<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egd6s5b0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egd6s5b0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:music-note-2" /></template>
