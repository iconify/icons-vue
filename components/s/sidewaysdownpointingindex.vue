<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwany8eak.css';
import '../../css/l/laefk-_jt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zwany8eak"/><path class="laefk-_jt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:sidewaysdownpointingindex" /></template>
