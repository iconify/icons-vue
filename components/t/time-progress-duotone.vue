<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoitpkywi.css';
import '../../css/j/j4nqo-26l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yoitpkywi"/><path class="j4nqo-26l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:time-progress-duotone" /></template>
