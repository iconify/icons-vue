<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqtxuqbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":18,"height":16};
const content = `<path class="rqtxuqbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:text-size" /></template>
