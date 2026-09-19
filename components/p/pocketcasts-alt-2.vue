<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xai6cac5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xai6cac5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:pocketcasts-alt-2" /></template>
