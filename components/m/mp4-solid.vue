<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnuh6xh8p.css';
import '../../css/f/fqore9c7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vnuh6xh8p"/><path clip-rule="evenodd" class="fqore9c7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:mp4-solid" /></template>
