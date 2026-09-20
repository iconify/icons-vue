<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjun9vdeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="wjun9vdeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:volumedown" /></template>
