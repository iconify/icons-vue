<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idk7jvbar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idk7jvbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:panel-left-round" /></template>
