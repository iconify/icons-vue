<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu3jh-bgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gu3jh-bgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vanilla-cookbook-light" /></template>
