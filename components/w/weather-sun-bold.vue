<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aps518b5a.css';
import '../../css/l/l41zmqbyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aps518b5a"/><path class="l41zmqbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:weather-sun-bold" /></template>
