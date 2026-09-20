<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6e1offvk.css';
import '../../css/a/a_xac3lyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s6e1offvk"/><path class="a_xac3lyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:reitti-light" /></template>
