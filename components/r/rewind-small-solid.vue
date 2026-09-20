<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/loilifxwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="loilifxwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:rewind-small-solid" /></template>
