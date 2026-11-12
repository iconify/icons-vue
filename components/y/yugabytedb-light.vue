<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lob7ambba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lob7ambba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yugabytedb-light" /></template>
