<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xce_36ygs.css';
import '../../css/u/u6urlybip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xce_36ygs"/><path class="u6urlybip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:people-group-duotone" /></template>
