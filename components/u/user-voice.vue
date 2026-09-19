<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjh0piecs.css';
import '../../css/t/tiru1tbyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjh0piecs"/><path class="tiru1tbyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:user-voice" /></template>
