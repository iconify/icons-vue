<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhbsr1bcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhbsr1bcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:square-full" /></template>
