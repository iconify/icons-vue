<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x84ld3txu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x84ld3txu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:mute-notification" /></template>
