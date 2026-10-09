<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8tz7uh6r.css';
import '../../css/l/lsbxu7b3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z8tz7uh6r"/><path class="lsbxu7b3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:nacelle-48" /></template>
