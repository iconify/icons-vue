<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kscz-0cog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kscz-0cog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:play" /></template>
