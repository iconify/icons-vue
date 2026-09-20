<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owt8m26yw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owt8m26yw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:road-fill" /></template>
