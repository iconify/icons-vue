<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-2ahia8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":34,"height":32};
const content = `<path class="t-2ahia8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:paperclip" /></template>
