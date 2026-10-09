<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsx9bkbtz.css';
import '../../css/k/kfvih2rid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jsx9bkbtz"/><path class="kfvih2rid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:zoom-out-20" /></template>
