<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quv4j8bda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="quv4j8bda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:microscope" /></template>
