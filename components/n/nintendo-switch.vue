<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co33ozbue.css';
import '../../css/p/piy19x2pb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="co33ozbue"/><path class="piy19x2pb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nintendo-switch" /></template>
