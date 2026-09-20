<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1kuc2bkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o1kuc2bkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:monero-light" /></template>
