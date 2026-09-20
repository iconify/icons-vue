<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6pvk5uvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6pvk5uvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:move-to-bottom-24" /></template>
