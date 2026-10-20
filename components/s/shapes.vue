<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmbv0z7pc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmbv0z7pc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:shapes" /></template>
