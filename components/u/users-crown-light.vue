<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu3wncbjp.css';
import '../../css/q/qa69btbsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu3wncbjp"/><path class="qa69btbsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:users-crown-light" /></template>
