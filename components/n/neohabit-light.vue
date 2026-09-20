<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqhkcqbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aqhkcqbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:neohabit-light" /></template>
