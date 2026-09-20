<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9nx0rcka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z9nx0rcka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:notifiarr-dark" /></template>
