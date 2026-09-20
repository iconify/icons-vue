<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw3n3ty8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sw3n3ty8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:mute-16" /></template>
