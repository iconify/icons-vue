<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p55d2obfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p55d2obfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-top-sharp-fill" /></template>
