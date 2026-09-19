<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx8sdnbnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xx8sdnbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-twitch" /></template>
