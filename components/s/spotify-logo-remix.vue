<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q570a2b8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="q570a2b8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:spotify-logo-remix" /></template>
