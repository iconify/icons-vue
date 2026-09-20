<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggo_ajzue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ggo_ajzue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tor-light" /></template>
