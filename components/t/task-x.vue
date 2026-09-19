<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/netr9ulfa.css';
import '../../css/k/kwu9_fbgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="netr9ulfa"/><path class="kwu9_fbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:task-x" /></template>
