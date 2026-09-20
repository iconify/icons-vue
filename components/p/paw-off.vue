<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz1r5ijls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mz1r5ijls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:paw-off" /></template>
