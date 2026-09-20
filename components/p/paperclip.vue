<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lj4vy298y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lj4vy298y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:paperclip" /></template>
