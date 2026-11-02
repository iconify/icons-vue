<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e82bg1ebl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e82bg1ebl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:spotify-fill" /></template>
