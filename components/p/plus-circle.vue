<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuqt_yb-q.css';
import '../../css/c/c6sfqyboe.css';
import '../../css/x/xfpsz_bsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uuqt_yb-q"/><path class="c6sfqyboe"/><path class="xfpsz_bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:plus-circle" /></template>
