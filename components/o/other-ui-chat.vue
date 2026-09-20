<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp_e8dmbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hp_e8dmbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:other-ui-chat" /></template>
