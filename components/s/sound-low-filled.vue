<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwxl3xbnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwxl3xbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:sound-low-filled" /></template>
