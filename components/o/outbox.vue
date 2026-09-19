<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kue-_9i_s.css';
import '../../css/w/wm0qy2b2m.css';
import '../../css/p/p91j9gb3y.css';
import '../../css/b/bl5dnqrrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kue-_9i_s"/><path class="wm0qy2b2m"/><path class="p91j9gb3y"/><path class="bl5dnqrrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:outbox" /></template>
