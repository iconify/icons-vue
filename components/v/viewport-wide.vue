<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-g_f4b1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-g_f4b1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:viewport-wide" /></template>
