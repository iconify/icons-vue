<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgbl27bzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgbl27bzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:okta" /></template>
