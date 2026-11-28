<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud500m9zk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ud500m9zk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:sidebar-plus" /></template>
