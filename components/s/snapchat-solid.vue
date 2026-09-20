<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzv361beg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wzv361beg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:snapchat-solid" /></template>
