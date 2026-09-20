<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n279pebde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n279pebde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:topology-star-2" /></template>
