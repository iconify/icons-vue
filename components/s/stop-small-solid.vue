<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pslwm0o8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pslwm0o8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:stop-small-solid" /></template>
