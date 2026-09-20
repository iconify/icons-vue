<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z58j8ibmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z58j8ibmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-nine-circle" /></template>
