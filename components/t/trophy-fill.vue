<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6ex7fpum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6ex7fpum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:trophy-fill" /></template>
