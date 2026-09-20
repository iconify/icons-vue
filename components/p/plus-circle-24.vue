<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6h96-z2f.css';
import '../../css/z/zj49idy7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6h96-z2f"/><path class="zj49idy7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:plus-circle-24" /></template>
