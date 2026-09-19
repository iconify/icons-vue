<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl0iderix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jl0iderix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:sticky-note-filled" /></template>
