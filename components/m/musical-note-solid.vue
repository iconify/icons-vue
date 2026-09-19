<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n970xwb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n970xwb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:musical-note-solid" /></template>
