<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b71gbhpxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b71gbhpxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:phone-top-right-with-greek-cross" /></template>
