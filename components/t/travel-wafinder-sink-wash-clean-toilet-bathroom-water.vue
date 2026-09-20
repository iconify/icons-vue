<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdmf3g-ko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="zdmf3g-ko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:travel-wafinder-sink-wash-clean-toilet-bathroom-water" /></template>
