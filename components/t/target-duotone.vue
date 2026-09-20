<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9m23kb1m.css';
import '../../css/s/sz3jedbeq.css';
import '../../css/x/x_4guwbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9m23kb1m"/><path class="sz3jedbeq"/><path class="x_4guwbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:target-duotone" /></template>
