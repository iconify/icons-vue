<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3gix-d_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b3gix-d_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:screenlite" /></template>
