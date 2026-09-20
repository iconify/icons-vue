<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt6ic24ut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bt6ic24ut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:soup-filled" /></template>
