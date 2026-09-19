<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqp6v8l5a.css';
import '../../css/z/zehpl8bdy.css';
import '../../css/l/llganab6s.css';
import '../../css/z/zyt9kcsds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqp6v8l5a"/><path class="zehpl8bdy"/><path class="llganab6s"/><path class="zyt9kcsds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:trpc" /></template>
