<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frr0t2b6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frr0t2b6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-sharp-fill" /></template>
