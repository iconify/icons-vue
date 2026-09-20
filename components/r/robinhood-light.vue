<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_udfug5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b_udfug5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:robinhood-light" /></template>
