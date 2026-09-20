<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa0-u8b8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aa0-u8b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nicehash" /></template>
