<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxy6xi-um.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jxy6xi-um"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:microphone-off" /></template>
