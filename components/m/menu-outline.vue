<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdq37lsuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jdq37lsuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:menu-outline" /></template>
