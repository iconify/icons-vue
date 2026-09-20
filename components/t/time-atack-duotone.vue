<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvsj4rbkk.css';
import '../../css/f/f42ipub-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="yvsj4rbkk"/><path class="f42ipub-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:time-atack-duotone" /></template>
