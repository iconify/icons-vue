<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6xiabc5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6xiabc5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rest-area-line" /></template>
