<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhs37gbzw.css';
import '../../css/e/ezc6ubmmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhs37gbzw"/><path class="ezc6ubmmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:smiley-cheeky" /></template>
