<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqy19wbvc.css';
import '../../css/q/qe0d046kd.css';
import '../../css/a/atzomcwel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":271};
const content = `<path class="cqy19wbvc"/><path class="qe0d046kd"/><path class="atzomcwel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pulumi" /></template>
