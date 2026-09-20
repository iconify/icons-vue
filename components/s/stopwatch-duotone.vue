<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oom6lfvzo.css';
import '../../css/s/s1yxkv7dc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oom6lfvzo"/><path class="s1yxkv7dc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:stopwatch-duotone" /></template>
