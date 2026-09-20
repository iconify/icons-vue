<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrmf9g2zn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xrmf9g2zn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:sound-off-outline" /></template>
