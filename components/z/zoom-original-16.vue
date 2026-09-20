<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orz0cib-a.css';
import '../../css/w/wm45_4p5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="orz0cib-a"/><path clip-rule="evenodd" class="wm45_4p5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:zoom-original-16" /></template>
