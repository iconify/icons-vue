<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdckqzbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdckqzbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:remove-formatting-round" /></template>
