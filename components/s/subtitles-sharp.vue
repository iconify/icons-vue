<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tef0-zbpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tef0-zbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:subtitles-sharp" /></template>
