<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq32g6yaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":29,"height":24};
const content = `<path class="wq32g6yaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:meetup" /></template>
