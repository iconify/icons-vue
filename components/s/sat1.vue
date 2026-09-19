<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8ann5b2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8ann5b2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sat1" /></template>
