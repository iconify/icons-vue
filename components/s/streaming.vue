<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x72w22bvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="x72w22bvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:streaming" /></template>
