<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvp5-2bby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lvp5-2bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:workersai-cloudflare" /></template>
