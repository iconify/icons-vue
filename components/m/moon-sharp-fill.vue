<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irzbusbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irzbusbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:moon-sharp-fill" /></template>
