<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1njp3l4b.css';
import '../../css/q/q9z9poh1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v1njp3l4b"/><path class="q9z9poh1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:moon-waning-crescent" /></template>
