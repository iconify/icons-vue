<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsj-lcc7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bsj-lcc7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nightlio-dark" /></template>
