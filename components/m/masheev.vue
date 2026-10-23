<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv6yjefwq.css';
import '../../css/l/lah9vyb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":120,"height":120};
const content = `<rect class="iv6yjefwq"/><path class="lah9vyb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:masheev" /></template>
