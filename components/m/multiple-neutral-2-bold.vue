<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvn7b8phk.css';
import '../../css/h/h07qv5bvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvn7b8phk"/><path class="h07qv5bvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:multiple-neutral-2-bold" /></template>
