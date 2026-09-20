<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/woe3q0b4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="woe3q0b4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-trending-up-sharp-fill" /></template>
