<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_ijomhgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z_ijomhgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:solectrus-light" /></template>
