<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w91-9k59o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w91-9k59o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:roast-filled" /></template>
