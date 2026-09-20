<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqaklac-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kqaklac-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:slack-solid" /></template>
