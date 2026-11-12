<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv7yabcbh.css';
import '../../css/t/t13q_mb5z.css';
import '../../css/r/r9_5sob_i.css';
import '../../css/b/b7yq6dbnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tv7yabcbh"/><path class="t13q_mb5z"/><path class="r9_5sob_i"/><path class="b7yq6dbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-word-dark" /></template>
