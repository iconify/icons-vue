<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pidtgwfoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pidtgwfoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rocket-chat-dark" /></template>
