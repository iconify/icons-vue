<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocxtnncco.css';
import '../../css/f/fb07yqbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocxtnncco"/><path class="fb07yqbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:tag" /></template>
