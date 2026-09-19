<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snfej5b-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="snfej5b-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:nine-of-bamboos-mahjong-filled" /></template>
