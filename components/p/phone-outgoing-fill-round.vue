<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf9hg6x8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kf9hg6x8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-outgoing-fill-round" /></template>
