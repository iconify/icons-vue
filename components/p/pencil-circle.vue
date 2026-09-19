<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry2mczbpi.css';
import '../../css/b/bwibdw4bb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b ry2mczbpi"/><path class="b bwibdw4bb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pencil-circle" /></template>
