<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhkscqhiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fhkscqhiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:target-filled" /></template>
