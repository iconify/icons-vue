<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzz3twymt.css';
import '../../css/p/p8lu4nblm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="rzz3twymt"/><path class="p8lu4nblm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:volume-muted-fill-12" /></template>
