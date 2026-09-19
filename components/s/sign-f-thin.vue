<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gihp7z99x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gihp7z99x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-f-thin" /></template>
