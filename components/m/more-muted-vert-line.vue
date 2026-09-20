<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqskjpbln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqskjpbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:more-muted-vert-line" /></template>
