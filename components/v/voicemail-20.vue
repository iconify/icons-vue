<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl6j6835z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bl6j6835z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:voicemail-20" /></template>
