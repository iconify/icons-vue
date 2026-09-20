<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as3o3em2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="as3o3em2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:shoe" /></template>
