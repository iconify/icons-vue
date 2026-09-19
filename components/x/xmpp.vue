<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyfj8kb6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="yyfj8kb6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:xmpp" /></template>
