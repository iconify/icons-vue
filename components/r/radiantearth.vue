<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wns20hxww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wns20hxww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:radiantearth" /></template>
