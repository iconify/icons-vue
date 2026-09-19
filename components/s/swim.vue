<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_9wi13wp.css';
import '../../css/j/jinb2jzjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="l_9wi13wp"/><path class="jinb2jzjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:swim" /></template>
