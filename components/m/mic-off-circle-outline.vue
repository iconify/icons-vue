<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anms5nb2o.css';
import '../../css/c/c9e9qbbyb.css';
import '../../css/h/hbq5upbdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="anms5nb2o"/><path class="c9e9qbbyb"/><path class="hbq5upbdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:mic-off-circle-outline" /></template>
