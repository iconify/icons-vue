<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy0650bub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zy0650bub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:microphone" /></template>
