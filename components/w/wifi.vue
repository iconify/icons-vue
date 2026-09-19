<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfcbzqdzf.css';
import '../../css/l/lqc9yhstq.css';
import '../../css/b/b8lwe5bdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="cfcbzqdzf"/><path clip-rule="evenodd" class="lqc9yhstq"/><path class="b8lwe5bdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:wifi" /></template>
