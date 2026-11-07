<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy096x3fo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dy096x3fo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:play-broken" /></template>
