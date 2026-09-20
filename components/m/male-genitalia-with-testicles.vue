<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6qxiac-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z6qxiac-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:male-genitalia-with-testicles" /></template>
