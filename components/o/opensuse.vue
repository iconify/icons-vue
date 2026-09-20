<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mybu-2pkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mybu-2pkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opensuse" /></template>
