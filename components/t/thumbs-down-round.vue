<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfu-blbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfu-blbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:thumbs-down-round" /></template>
