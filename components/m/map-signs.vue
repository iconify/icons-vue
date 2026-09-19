<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btfnhwxyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1728,"height":1792};
const content = `<path class="btfnhwxyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:map-signs" /></template>
