<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abm-7gbxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abm-7gbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:share" /></template>
