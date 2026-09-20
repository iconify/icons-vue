<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0bkqib-z.css';
import '../../css/h/h9ba1ntbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0bkqib-z"/><path class="h9ba1ntbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:professions-man-astronaut-bold" /></template>
