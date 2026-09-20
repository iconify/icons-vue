<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo25cncdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qo25cncdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:spaceship" /></template>
