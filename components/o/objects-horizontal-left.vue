<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4tqe28pg.css';
import '../../css/r/rfi2jbchm.css';
import '../../css/e/eb9scq8yj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4tqe28pg"/><rect class="rfi2jbchm"/><rect class="eb9scq8yj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:objects-horizontal-left" /></template>
