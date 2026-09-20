<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahur8ibka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ahur8ibka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:radio-tower" /></template>
