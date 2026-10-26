<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0t-izetn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v0t-izetn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:sparkle-heart" /></template>
