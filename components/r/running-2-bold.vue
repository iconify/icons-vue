<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shc5ox2kp.css';
import '../../css/j/jerfmgb3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shc5ox2kp"/><path clip-rule="evenodd" class="jerfmgb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:running-2-bold" /></template>
