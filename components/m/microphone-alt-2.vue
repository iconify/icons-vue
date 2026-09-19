<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aq0bsubtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aq0bsubtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:microphone-alt-2" /></template>
