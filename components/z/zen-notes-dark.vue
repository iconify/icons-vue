<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ive8xobqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ive8xobqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zen-notes-dark" /></template>
