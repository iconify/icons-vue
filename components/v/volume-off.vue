<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlqo4qu-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlqo4qu-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:volume-off" /></template>
