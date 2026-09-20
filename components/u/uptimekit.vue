<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkei5sq7u.css';
import '../../css/q/qy8hd1btp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vkei5sq7u"/><path class="qy8hd1btp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:uptimekit" /></template>
