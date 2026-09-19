<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcw_0vb3n.css';
import '../../css/r/ro-apk0gw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xcw_0vb3n"/><path class="ro-apk0gw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:scan" /></template>
