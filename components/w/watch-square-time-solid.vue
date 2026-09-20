<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aglw7i7ro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aglw7i7ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:watch-square-time-solid" /></template>
