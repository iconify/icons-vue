<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo5_wobsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo5_wobsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mastodon-fill" /></template>
