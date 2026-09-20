<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at3xiib2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="at3xiib2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:publish-document" /></template>
