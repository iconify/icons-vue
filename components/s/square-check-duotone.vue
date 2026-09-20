<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdrmlmx_y.css';
import '../../css/y/ytv8j6l6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdrmlmx_y"/><path class="ytv8j6l6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:square-check-duotone" /></template>
