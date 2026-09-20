<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r25y7b4nf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r25y7b4nf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zulip-light" /></template>
