<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-tyk1b5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="y-tyk1b5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:workspace-desk" /></template>
