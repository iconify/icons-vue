<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtbzzkg9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wtbzzkg9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:racetrack-horse" /></template>
