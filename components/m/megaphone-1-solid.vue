<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia5v6ebka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ia5v6ebka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:megaphone-1-solid" /></template>
