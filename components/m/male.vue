<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmc12mo1y.css';
import '../../css/g/g6nhfybzv.css';
import '../../css/c/cyo88nvfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jmc12mo1y"/><path class="g6nhfybzv"/><path class="cyo88nvfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:male" /></template>
