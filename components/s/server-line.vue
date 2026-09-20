<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9m8-rbzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9m8-rbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:server-line" /></template>
