<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvqgryrqk.css';
import '../../css/t/taxqw2bmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kvqgryrqk"/><path class="taxqw2bmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:watch-15" /></template>
