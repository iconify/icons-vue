<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw0hygbgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hw0hygbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:streamlake" /></template>
