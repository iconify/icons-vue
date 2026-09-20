<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo8oo-9-t.css';
import '../../css/h/h3xx9zf8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fo8oo-9-t"/><path class="h3xx9zf8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:profilarr-light" /></template>
