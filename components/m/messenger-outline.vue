<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iak_x3heq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="iak_x3heq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:messenger-outline" /></template>
