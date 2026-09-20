<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5vpj0gqk.css';
import '../../css/m/m87stabfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5vpj0gqk"/><path class="m87stabfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:playlist-solid" /></template>
