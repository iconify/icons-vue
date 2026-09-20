<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvi0-fb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvi0-fb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-voice-sharp" /></template>
