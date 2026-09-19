<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjqfd70iz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjqfd70iz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:navigation-off" /></template>
