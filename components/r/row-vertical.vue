<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi7nx8bft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi7nx8bft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:row-vertical" /></template>
