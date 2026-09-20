<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmhuaub_w.css';
import '../../css/o/ofyg4tbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jmhuaub_w"/><path class="ofyg4tbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:manhole" /></template>
