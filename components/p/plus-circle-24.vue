<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2aw66r3l.css';
import '../../css/w/wvsyf7maw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2aw66r3l"/><path clip-rule="evenodd" class="wvsyf7maw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:plus-circle-24" /></template>
