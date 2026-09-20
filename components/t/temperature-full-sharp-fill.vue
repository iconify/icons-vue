<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzwib_bbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzwib_bbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:temperature-full-sharp-fill" /></template>
