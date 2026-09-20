<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-3cwvmmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y-3cwvmmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:skype-outline" /></template>
