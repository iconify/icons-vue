<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt39gtb6i.css';
import '../../css/f/fk2bifb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt39gtb6i"/><path class="fk2bifb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:signin-alt" /></template>
