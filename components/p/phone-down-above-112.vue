<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo01rrp1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zo01rrp1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:phone-down-above-112" /></template>
