<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp3f46b8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wp3f46b8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:portainer" /></template>
