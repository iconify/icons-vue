<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi7c8xbbv.css';
import '../../css/b/b8j05vb5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oi7c8xbbv"/><path class="b8j05vb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:xbox-game-pass" /></template>
