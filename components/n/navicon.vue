<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glgc2s32b.css';
import '../../css/t/t6zyl3h8b.css';
import '../../css/n/naljiqsza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="glgc2s32b"/><path class="t6zyl3h8b"/><path class="naljiqsza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:navicon" /></template>
