<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhgxw2lrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhgxw2lrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:slack-fill" /></template>
