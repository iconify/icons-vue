<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_ghebcwv.css';
import '../../css/f/f7hsq-06y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p_ghebcwv"/><path clip-rule="evenodd" class="f7hsq-06y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:skull-solid" /></template>
