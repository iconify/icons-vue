<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q14syjb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q14syjb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-left-close-sharp-fill" /></template>
