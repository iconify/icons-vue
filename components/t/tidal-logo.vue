<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjmi7louc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjmi7louc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:tidal-logo" /></template>
