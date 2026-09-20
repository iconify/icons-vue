<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/heccx78bv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="heccx78bv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:medassist-light" /></template>
