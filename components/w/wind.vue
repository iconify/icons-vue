<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6-4j0b6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6-4j0b6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:wind" /></template>
