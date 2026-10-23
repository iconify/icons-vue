<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn_4rw0pb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nn_4rw0pb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:zodiac-virgo" /></template>
