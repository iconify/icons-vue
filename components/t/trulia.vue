<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf8j2-5ha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wf8j2-5ha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:trulia" /></template>
