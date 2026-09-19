<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgx-9abtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgx-9abtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:patreon" /></template>
