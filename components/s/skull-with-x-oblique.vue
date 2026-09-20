<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj--35xot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sj--35xot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:skull-with-x-oblique" /></template>
