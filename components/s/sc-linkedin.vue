<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvdvcxqfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="hvdvcxqfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:sc-linkedin" /></template>
