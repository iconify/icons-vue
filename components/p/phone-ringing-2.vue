<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5susob-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="r5susob-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:phone-ringing-2" /></template>
