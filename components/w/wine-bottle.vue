<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv2j-pbiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rv2j-pbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wine-bottle" /></template>
