<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk4qf0b7g.css';
import '../../css/g/gjtzg1bku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yk4qf0b7g"/><path class="gjtzg1bku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:message-square-error" /></template>
