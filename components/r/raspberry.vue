<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kixwr7b0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kixwr7b0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:raspberry" /></template>
