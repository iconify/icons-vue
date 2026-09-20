<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea7m5uaqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea7m5uaqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:wikibooks" /></template>
