<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5ucif9jw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r5ucif9jw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:privadovpn-dark" /></template>
