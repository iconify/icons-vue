<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1dqn_bgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-0.5,"top":-0.5};
const content = `<path class="p1dqn_bgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:write-f" /></template>
