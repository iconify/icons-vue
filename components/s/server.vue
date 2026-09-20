<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9xgz4b1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9xgz4b1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:server" /></template>
