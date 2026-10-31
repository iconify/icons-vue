<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln93r60js.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ln93r60js"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:x-round" /></template>
