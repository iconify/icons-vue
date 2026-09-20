<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf6ap-4vf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jf6ap-4vf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:video-replace" /></template>
