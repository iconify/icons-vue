<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf_rons6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wf_rons6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:potted-plant" /></template>
