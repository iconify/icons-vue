<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa9pn04_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xa9pn04_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:unlock-line" /></template>
