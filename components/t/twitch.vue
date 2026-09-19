<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tudukm9ae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tudukm9ae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:twitch" /></template>
