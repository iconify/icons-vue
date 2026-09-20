<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-06obvoh.css';
import '../../css/l/ly4zvcbhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-06obvoh"/><path class="ly4zvcbhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:settings-1-line" /></template>
