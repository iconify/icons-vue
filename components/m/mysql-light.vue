<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w84gw5bsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w84gw5bsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mysql-light" /></template>
