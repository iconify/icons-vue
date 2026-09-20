<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbmck-b3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qbmck-b3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:redwoodjs-outline" /></template>
