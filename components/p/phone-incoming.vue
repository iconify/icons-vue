<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qryyscb4x.css';
import '../../css/s/siitcdcqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qryyscb4x"/><path class="siitcdcqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:phone-incoming" /></template>
