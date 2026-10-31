<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skpsf7bnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skpsf7bnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:scissors-gloss" /></template>
