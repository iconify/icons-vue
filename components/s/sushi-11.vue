<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9x4zmb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="s9x4zmb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:sushi-11" /></template>
