<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4i5z2h2q.css';
import '../../css/c/c4uvzi6dm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="j4i5z2h2q"/><path class="c4uvzi6dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pushover" /></template>
