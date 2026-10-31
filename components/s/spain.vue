<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxqv83arr.css';
import '../../css/u/ub6441bsg.css';
import '../../css/g/gv5rgxxwr.css';
import '../../css/v/v46merb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="sxqv83arr"/><path class="ub6441bsg"/><path class="gv5rgxxwr"/><path class="v46merb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:spain" /></template>
