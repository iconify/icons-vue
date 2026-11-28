<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atseoh4ew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atseoh4ew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:megaphone-alert" /></template>
