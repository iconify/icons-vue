<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nge32vmzt.css';
import '../../css/n/nic302jho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nge32vmzt"/><path class="nic302jho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:target-light" /></template>
