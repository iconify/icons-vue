<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsbfe76of.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lsbfe76of"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:user-avatar-outline" /></template>
