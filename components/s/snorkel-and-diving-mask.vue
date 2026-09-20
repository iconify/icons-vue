<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njd2r1b1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="njd2r1b1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:snorkel-and-diving-mask" /></template>
