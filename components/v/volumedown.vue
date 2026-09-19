<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw_s9xb-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":897,"height":1024};
const content = `<path class="kw_s9xb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:volumedown" /></template>
