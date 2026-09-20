<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phfr-hjhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="phfr-hjhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:t" /></template>
