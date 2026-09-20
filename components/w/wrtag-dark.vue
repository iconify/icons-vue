<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4fb74sia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g4fb74sia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wrtag-dark" /></template>
