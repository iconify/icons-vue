<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im1he9aee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="im1he9aee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wger-dark" /></template>
