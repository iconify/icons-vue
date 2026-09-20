<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot1g9j7yp.css';
import '../../css/f/fh44hvb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ot1g9j7yp"/><path class="fh44hvb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:retro-pc" /></template>
