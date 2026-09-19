<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3-mg25mz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3-mg25mz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:monitor-filled" /></template>
