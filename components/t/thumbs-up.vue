<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nta_beb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nta_beb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:thumbs-up" /></template>
