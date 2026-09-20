<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtd4pnnoa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtd4pnnoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scan-face-sharp-fill" /></template>
