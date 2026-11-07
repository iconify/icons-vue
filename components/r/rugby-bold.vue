<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-mei2b6d.css';
import '../../css/n/nudj6ubep.css';
import '../../css/g/gl_0n93vk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-mei2b6d"/><path class="nudj6ubep"/><path clip-rule="evenodd" class="gl_0n93vk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rugby-bold" /></template>
