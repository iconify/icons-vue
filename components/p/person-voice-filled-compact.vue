<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqvpvccbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xqvpvccbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:person-voice-filled-compact" /></template>
