<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8dx6q3cz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8dx6q3cz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-sharp-duotone" /></template>
