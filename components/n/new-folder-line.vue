<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgbi-g60n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgbi-g60n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:new-folder-line" /></template>
