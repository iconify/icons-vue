<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d01g2lbqs.css';
import '../../css/i/ijt9r4b8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d01g2lbqs"/><path class="ijt9r4b8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:search-split-light" /></template>
