<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec-dkicym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ec-dkicym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:pound-circle-remix" /></template>
