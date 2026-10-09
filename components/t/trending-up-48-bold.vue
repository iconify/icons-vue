<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7o6v4tnd.css';
import '../../css/r/rargr9bqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j7o6v4tnd"/><path class="rargr9bqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:trending-up-48-bold" /></template>
