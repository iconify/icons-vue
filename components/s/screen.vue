<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5kweu8nd.css';
import '../../css/y/yj9yfrb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k5kweu8nd"/><path class="yj9yfrb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:screen" /></template>
