<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypa60bcwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ypa60bcwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mind-map-fill" /></template>
