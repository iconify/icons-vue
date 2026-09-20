<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si-73mbtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="si-73mbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:tired" /></template>
