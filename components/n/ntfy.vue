<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icge5ubjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icge5ubjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ntfy" /></template>
