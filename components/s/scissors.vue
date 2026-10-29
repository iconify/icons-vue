<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z75kw-b6j.css';
import '../../css/t/thhb5jvkd.css';
import '../../css/p/p6qe0dtvu.css';
import '../../css/g/g43g2-bnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k z75kw-b6j"/><path class="thhb5jvkd wm-k"/><path class="p6qe0dtvu wm-k"/><path class="g43g2-bnc wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:scissors" /></template>
