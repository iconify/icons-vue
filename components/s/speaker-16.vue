<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7kzsmf7u.css';
import '../../css/s/s9rahug_l.css';
import '../../css/v/vx3hl8b7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="i7kzsmf7u"/><path class="s9rahug_l"/><path class="vx3hl8b7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:speaker-16" /></template>
