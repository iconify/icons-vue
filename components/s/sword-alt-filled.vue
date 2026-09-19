<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp6gv5bfm.css';
import '../../css/q/ql5n44bqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wp6gv5bfm"/><path class="ql5n44bqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sword-alt-filled" /></template>
