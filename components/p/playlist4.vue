<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt9503pkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rt9503pkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:playlist4" /></template>
