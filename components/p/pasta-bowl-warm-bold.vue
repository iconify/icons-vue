<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsur8-ztq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsur8-ztq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:pasta-bowl-warm-bold" /></template>
