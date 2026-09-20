<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww0ts7b9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ww0ts7b9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:patreon" /></template>
