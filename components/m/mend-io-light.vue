<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b808q8dsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b808q8dsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mend-io-light" /></template>
