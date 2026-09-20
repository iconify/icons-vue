<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unnhiupqa.css';
import '../../css/o/o64ssnoeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="unnhiupqa"/><path class="o64ssnoeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:pivot-column-16" /></template>
