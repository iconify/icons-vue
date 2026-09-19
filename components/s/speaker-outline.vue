<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucgba-79t.css';
import '../../css/y/yeeel25yq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucgba-79t"/><path class="yeeel25yq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:speaker-outline" /></template>
