<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfq2nobmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vfq2nobmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-caret-right-sharp-fill" /></template>
