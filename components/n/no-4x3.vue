<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyroak62h.css';
import '../../css/j/jtbbcksnj.css';
import '../../css/l/lm6pm0b8y.css';
import '../../css/d/ddczr-bbd.css';
import '../../css/c/cl6jqfbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="lyroak62h"/><path class="jtbbcksnj"/><path class="lm6pm0b8y"/><path class="ddczr-bbd"/><path class="cl6jqfbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:no-4x3" /></template>
