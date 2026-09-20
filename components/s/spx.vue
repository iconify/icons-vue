<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qapg4nbep.css';
import '../../css/r/rk99s4m6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qapg4nbep"/><path class="rk99s4m6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:spx" /></template>
