<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs1lgy2sf.css';
import '../../css/f/ft-qacc5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qs1lgy2sf"/><path class="ft-qacc5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:task-list-pin-bold" /></template>
