<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9s7-rhuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q9s7-rhuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:overcast-logo-solid" /></template>
