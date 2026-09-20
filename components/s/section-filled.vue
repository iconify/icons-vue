<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fary13bkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fary13bkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:section-filled" /></template>
