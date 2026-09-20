<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1f-ugyov.css';
import '../../css/r/r6-wpcu2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1f-ugyov"/><path class="r6-wpcu2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:stars" /></template>
