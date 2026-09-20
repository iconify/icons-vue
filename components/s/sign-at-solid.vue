<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofw0-zwkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ofw0-zwkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:sign-at-solid" /></template>
