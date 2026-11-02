<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgzjxtbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgzjxtbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-circle-off-fill" /></template>
