<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb4dekbxd.css';
import '../../css/r/rq3rv_bun.css';
import '../../css/k/k3szck9dr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":400,"height":400};
const content = `<path class="jb4dekbxd"/><path class="rq3rv_bun"/><path class="k3szck9dr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:warp" /></template>
