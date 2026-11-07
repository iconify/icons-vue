<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-yckdk2x.css';
import '../../css/k/kdm4lcb3e.css';
import '../../css/s/seqcy-7oq.css';
import '../../css/l/lri0zsbsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-yckdk2x"/><path class="kdm4lcb3e"/><path class="seqcy-7oq"/><path class="lri0zsbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wi-fi-bold" /></template>
