<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et91lnbbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="et91lnbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:reddit-downvote-light" /></template>
