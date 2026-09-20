<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjuc-_2op.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjuc-_2op"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:semaphore-ci" /></template>
