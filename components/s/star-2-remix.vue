<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9msasz7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k9msasz7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:star-2-remix" /></template>
