<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eneku41ut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eneku41ut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:marpui-dark" /></template>
