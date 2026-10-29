<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thj3mqbqh.css';
import '../../css/u/uqi_583re.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thj3mqbqh wm-k"/><path class="uqi_583re wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:subscript" /></template>
