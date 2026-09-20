<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b441swb4b.css';
import '../../css/f/fkf53bc3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b441swb4b"/><path class="fkf53bc3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:select-single-16" /></template>
