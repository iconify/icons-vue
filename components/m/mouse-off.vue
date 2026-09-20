<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1mq-0jsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1mq-0jsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:mouse-off" /></template>
