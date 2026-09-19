<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlort3k_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tlort3k_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:speech-bubble-ellipsis" /></template>
