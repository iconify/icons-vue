<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe5kl4b5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="pe5kl4b5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:uni6709-box" /></template>
