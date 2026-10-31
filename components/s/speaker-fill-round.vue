<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbw5gmbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbw5gmbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:speaker-fill-round" /></template>
