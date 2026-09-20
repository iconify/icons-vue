<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6-wj17uh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w6-wj17uh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:star-solid" /></template>
