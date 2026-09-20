<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcnue7btn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wcnue7btn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-pause-fill" /></template>
