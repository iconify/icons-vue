<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0lx0cb_d.css';
import '../../css/w/wmq89w7_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0lx0cb_d"/><path class="wmq89w7_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:system-marked-filled" /></template>
