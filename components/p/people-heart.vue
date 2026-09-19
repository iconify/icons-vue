<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re4n0ebks.css';
import '../../css/a/a01wef02w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="re4n0ebks"/><path class="a01wef02w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:people-heart" /></template>
