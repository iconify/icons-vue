<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zenilsb6y.css';
import '../../css/v/veupicb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zenilsb6y"/><path class="veupicb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-parking-off-filled" /></template>
