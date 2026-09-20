<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyvpw6bqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyvpw6bqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:robot-off" /></template>
