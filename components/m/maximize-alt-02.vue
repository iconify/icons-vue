<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh60tvb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rh60tvb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:maximize-alt-02" /></template>
