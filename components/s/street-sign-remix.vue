<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9x6irbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="g9x6irbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:street-sign-remix" /></template>
