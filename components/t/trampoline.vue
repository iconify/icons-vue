<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of3dkvhwn.css';
import '../../css/f/f5456gr9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="of3dkvhwn"/><path class="f5456gr9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:trampoline" /></template>
