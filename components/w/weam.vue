<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bogfzjklk.css';
import '../../css/r/rv75bablh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bogfzjklk"/><path class="rv75bablh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:weam" /></template>
