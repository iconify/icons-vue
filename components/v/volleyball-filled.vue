<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz3hkhzdn.css';
import '../../css/l/l_7dq0ahs.css';
import '../../css/p/pun1k1brn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz3hkhzdn"/><path class="l_7dq0ahs"/><path class="pun1k1brn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:volleyball-filled" /></template>
