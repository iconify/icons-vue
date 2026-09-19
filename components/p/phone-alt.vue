<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjq2_lbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bjq2_lbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:phone-alt" /></template>
