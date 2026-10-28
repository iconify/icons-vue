<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdo10pb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdo10pb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:moon" /></template>
