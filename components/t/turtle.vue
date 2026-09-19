<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8bygjb1r.css';
import '../../css/c/c8y7okrif.css';
import '../../css/d/d3fqriehb.css';
import '../../css/y/yga48zbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y8bygjb1r"/><path class="c8y7okrif"/><path class="d3fqriehb"/><path class="yga48zbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:turtle" /></template>
