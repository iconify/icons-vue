<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj70oivdq.css';
import '../../css/a/a7pe4ku8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sj70oivdq"/><path class="a7pe4ku8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:timer" /></template>
