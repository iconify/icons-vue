<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b44mov6pv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b44mov6pv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:theater-curtains" /></template>
