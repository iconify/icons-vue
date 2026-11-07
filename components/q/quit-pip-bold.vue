<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz0u67btj.css';
import '../../css/x/x3oufibth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tz0u67btj"/><path class="x3oufibth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:quit-pip-bold" /></template>
