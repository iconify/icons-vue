<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpvilr8cp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpvilr8cp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sultan-group-hung" /></template>
