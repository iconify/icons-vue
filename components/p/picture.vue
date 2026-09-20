<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atxcznbro.css';
import '../../css/k/knpqz8bcw.css';
import '../../css/v/v93089bzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="atxcznbro"/><ellipse class="knpqz8bcw"/><path class="v93089bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:picture" /></template>
