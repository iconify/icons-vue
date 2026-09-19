<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh-17nb3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jh-17nb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:zap" /></template>
