<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw2t20ski.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="rw2t20ski"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:pause-circle-solid" /></template>
