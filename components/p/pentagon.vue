<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7mn-8b2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7mn-8b2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:pentagon" /></template>
