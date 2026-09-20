<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b45l35wcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b45l35wcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:termix-light" /></template>
