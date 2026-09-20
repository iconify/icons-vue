<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruwzk5v4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ruwzk5v4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:vkontakte-line" /></template>
