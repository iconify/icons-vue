<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0qooqlqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0qooqlqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:settings-2" /></template>
