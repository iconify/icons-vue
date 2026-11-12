<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igxg7ab5n.css';
import '../../css/a/aw61reb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="igxg7ab5n"/><path class="aw61reb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sunshine-light" /></template>
