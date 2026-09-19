<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-n25z4ll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-n25z4ll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:open-webui" /></template>
