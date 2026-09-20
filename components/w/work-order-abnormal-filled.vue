<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4sc0yb1a.css';
import '../../css/q/qcjn5ubrr.css';
import '../../css/a/avgingbgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j4sc0yb1a"/><path class="qcjn5ubrr"/><path clip-rule="evenodd" class="avgingbgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:work-order-abnormal-filled" /></template>
