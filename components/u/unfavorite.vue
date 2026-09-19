<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgv87b72c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="rgv87b72c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:unfavorite" /></template>
