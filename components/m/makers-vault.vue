<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unp_99osw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="unp_99osw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:makers-vault" /></template>
