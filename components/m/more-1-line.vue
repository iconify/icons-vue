<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7q918bhw.css';
import '../../css/q/qmjk3ab0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7q918bhw"/><path class="qmjk3ab0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:more-1-line" /></template>
