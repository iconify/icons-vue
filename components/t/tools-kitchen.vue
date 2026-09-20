<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clmzk40qm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clmzk40qm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:tools-kitchen" /></template>
