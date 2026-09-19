<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5rhzabru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="g5rhzabru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:television-filled" /></template>
