<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5l64hbja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k5l64hbja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:suitcase-2" /></template>
