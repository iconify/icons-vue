<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s50kqrtcf.css';
import '../../css/i/iwrg-gb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s50kqrtcf"/><path class="iwrg-gb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:more-2-line" /></template>
