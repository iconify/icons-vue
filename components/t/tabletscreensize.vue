<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js_8mh9rd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":768};
const content = `<path class="js_8mh9rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:tabletscreensize" /></template>
