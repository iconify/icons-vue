<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj27_bokn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rj27_bokn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:rewind" /></template>
