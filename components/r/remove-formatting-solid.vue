<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/feolb4bfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="feolb4bfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:remove-formatting-solid" /></template>
