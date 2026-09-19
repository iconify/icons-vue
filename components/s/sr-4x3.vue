<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5vdclnqy.css';
import '../../css/o/ot7rdzb2f.css';
import '../../css/b/bdg0p2bxg.css';
import '../../css/l/l_6g95bgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="n5vdclnqy"/><path class="ot7rdzb2f"/><path class="bdg0p2bxg"/><path class="l_6g95bgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:sr-4x3" /></template>
