<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5c4dtb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5c4dtb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:roobee" /></template>
