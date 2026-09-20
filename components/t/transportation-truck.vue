<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9xke1qvt.css';
import '../../css/u/u71vq3b-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u9xke1qvt"/><path class="u71vq3b-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:transportation-truck" /></template>
