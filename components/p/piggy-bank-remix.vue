<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdpcdabdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="sdpcdabdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:piggy-bank-remix" /></template>
