<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0bs2lpng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0bs2lpng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:sensors-2" /></template>
