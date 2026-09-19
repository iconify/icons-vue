<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn3iwubds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fn3iwubds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:no-alcohol" /></template>
