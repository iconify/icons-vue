<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldn3htbux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ldn3htbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:stopwatch-solid" /></template>
