<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gipm5jb6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gipm5jb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:netbox-light" /></template>
