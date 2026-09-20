<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj4co0bsz.css';
import '../../css/a/aaj4a2bie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="oj4co0bsz"/><path class="aaj4a2bie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:mast-lighting" /></template>
