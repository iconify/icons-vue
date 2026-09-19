<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6qgsn_0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":25};
const content = `<path class="u6qgsn_0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:references" /></template>
