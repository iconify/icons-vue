<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if170pbef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="if170pbef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:sauce-labs" /></template>
