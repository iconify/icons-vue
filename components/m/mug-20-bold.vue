<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwcvxfb2t.css';
import '../../css/y/yo1jbmxse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dwcvxfb2t"/><path class="yo1jbmxse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mug-20-bold" /></template>
