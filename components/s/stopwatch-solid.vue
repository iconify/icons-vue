<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agydu2b-r.css';
import '../../css/w/w26aucbxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="agydu2b-r"/><path clip-rule="evenodd" class="w26aucbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:stopwatch-solid" /></template>
