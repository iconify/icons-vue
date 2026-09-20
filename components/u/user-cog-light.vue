<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8oo03bfv.css';
import '../../css/o/o9-v1yxgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8oo03bfv"/><path class="o9-v1yxgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:user-cog-light" /></template>
