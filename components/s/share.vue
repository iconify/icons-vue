<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gus-xabuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gus-xabuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:share" /></template>
