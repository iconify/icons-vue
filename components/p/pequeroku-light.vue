<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4fj0mnqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l4fj0mnqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pequeroku-light" /></template>
