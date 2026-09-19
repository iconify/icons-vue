<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7daywb0g.css';
import '../../css/m/m8bpqrxix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="a7daywb0g"/><path class="m8bpqrxix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:user" /></template>
