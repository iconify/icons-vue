<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3cff8b-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c3cff8b-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sofi" /></template>
