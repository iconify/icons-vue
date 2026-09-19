<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akta-9j2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="akta-9j2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:view-2d" /></template>
