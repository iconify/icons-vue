<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzncnobio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vzncnobio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-settings-corner-fill-round" /></template>
