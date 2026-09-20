<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5tpa0s6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="o5tpa0s6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:patreon-solid" /></template>
