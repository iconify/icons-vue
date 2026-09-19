<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsi41yb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vsi41yb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:typescript-test" /></template>
