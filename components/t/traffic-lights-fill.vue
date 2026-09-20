<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9gx3uspy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9gx3uspy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:traffic-lights-fill" /></template>
